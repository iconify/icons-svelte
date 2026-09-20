<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrq-4jbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="zrq-4jbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:rail-11" {...props}></Icon>
