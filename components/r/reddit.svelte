<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwro-z_xc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwro-z_xc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:reddit" {...props}></Icon>
