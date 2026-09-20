<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuledqeat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kuledqeat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:notifications" {...props}></Icon>
