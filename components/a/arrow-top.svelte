<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5e98f89i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="f5e98f89i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:arrow-top" {...props}></Icon>
