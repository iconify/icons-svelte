<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr6x52bhh.css';
import '../../css/a/ai5lobbna.css';
import '../../css/t/tkspbcueb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rr6x52bhh"/><path class="ai5lobbna"/><path class="tkspbcueb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pg-back-web-dark" {...props}></Icon>
