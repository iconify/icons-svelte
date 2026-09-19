<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap45321cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ap45321cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:grid" {...props}></Icon>
