<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq-pjebth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1280,"height":1760};
const content = `<path class="jq-pjebth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:female" {...props}></Icon>
