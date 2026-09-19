<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay78_wwsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ay78_wwsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:palm-down-hand" {...props}></Icon>
