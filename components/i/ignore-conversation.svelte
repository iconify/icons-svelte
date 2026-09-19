<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2_7nq0-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="o2_7nq0-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:ignore-conversation" {...props}></Icon>
