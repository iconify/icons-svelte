<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8h0a1vdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="u8h0a1vdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:bug-sync" {...props}></Icon>
