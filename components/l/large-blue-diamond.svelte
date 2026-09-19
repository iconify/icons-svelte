<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytsullcxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ytsullcxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:large-blue-diamond" {...props}></Icon>
