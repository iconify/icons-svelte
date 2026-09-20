<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxzpyfhvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wxzpyfhvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coughing-face-with-phlegm-in-circle-outline" {...props}></Icon>
