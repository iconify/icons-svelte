<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf7v85bwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mf7v85bwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:financial" {...props}></Icon>
