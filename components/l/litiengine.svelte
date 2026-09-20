<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyr61nbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyr61nbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:litiengine" {...props}></Icon>
