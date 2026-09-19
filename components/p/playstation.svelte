<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh_r0wb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dh_r0wb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:playstation" {...props}></Icon>
