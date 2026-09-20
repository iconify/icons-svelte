<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh4_34evi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="yh4_34evi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:clock" {...props}></Icon>
