<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqwj2_7hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="hqwj2_7hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:apple-whole" {...props}></Icon>
