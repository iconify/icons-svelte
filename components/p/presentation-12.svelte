<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dco8gj7_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dco8gj7_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:presentation-12" {...props}></Icon>
