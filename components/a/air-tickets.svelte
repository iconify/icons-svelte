<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6m7mzbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="q6m7mzbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:air-tickets" {...props}></Icon>
