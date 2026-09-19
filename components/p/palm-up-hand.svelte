<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-06_rfwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y-06_rfwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:palm-up-hand" {...props}></Icon>
