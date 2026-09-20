<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfhjeo_yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfhjeo_yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:deutsche-telekom" {...props}></Icon>
