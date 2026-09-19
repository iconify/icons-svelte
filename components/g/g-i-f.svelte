<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-6z77lgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="q-6z77lgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:g-i-f" {...props}></Icon>
