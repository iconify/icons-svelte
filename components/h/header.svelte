<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6g495_-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="t6g495_-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:header" {...props}></Icon>
