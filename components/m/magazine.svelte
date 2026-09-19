<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlryto17e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":897,"height":1024};
const content = `<path class="nlryto17e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:magazine" {...props}></Icon>
