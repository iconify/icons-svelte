<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irboz257l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irboz257l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:imagedotsc" {...props}></Icon>
