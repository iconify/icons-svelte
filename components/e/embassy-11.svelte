<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwnm_cc8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="uwnm_cc8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:embassy-11" {...props}></Icon>
