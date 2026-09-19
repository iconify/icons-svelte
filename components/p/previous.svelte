<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv4yel-fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":224,"height":472};
const content = `<path class="zv4yel-fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:previous" {...props}></Icon>
