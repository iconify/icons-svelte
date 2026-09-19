<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn-1o2b-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="cn-1o2b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:caret-solid-up" {...props}></Icon>
