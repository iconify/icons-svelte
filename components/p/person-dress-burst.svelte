<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av5c-t6zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="av5c-t6zb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-dress-burst" {...props}></Icon>
