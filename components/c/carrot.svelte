<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5fq7hrmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d5fq7hrmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:carrot" {...props}></Icon>
