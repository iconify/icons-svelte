<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr-m91bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pr-m91bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:onion" {...props}></Icon>
