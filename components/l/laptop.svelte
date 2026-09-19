<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anuoaabbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="anuoaabbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:laptop" {...props}></Icon>
