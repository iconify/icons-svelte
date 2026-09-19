<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1j879b-l.css';
import '../../css/p/pg468fg1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a1j879b-l"/><path class="pg468fg1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rain-drizzle" {...props}></Icon>
