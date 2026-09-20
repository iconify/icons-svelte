<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0o14rb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y0o14rb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:less-than" {...props}></Icon>
