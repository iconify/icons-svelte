<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0f1rtbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="c0f1rtbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:pause" {...props}></Icon>
