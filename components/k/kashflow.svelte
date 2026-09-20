<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br0tc3bwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="br0tc3bwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kashflow" {...props}></Icon>
