<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe_ubo__v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xe_ubo__v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:oncoming-taxi" {...props}></Icon>
