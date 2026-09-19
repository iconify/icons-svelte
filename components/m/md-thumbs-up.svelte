<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quacllbqi.css';
import '../../css/c/cily1qbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="quacllbqi"/><path class="cily1qbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-thumbs-up" {...props}></Icon>
