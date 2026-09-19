<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy0brxbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="wy0brxbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:percent" {...props}></Icon>
