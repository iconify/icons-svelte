<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix_37863o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ix_37863o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-solid-duo" {...props}></Icon>
