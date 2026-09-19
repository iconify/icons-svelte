<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqe3ykbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rqe3ykbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:high-voltage" {...props}></Icon>
