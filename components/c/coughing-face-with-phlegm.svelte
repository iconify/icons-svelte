<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucy80rbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ucy80rbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coughing-face-with-phlegm" {...props}></Icon>
