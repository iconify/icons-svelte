<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udl_u4bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="udl_u4bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:bluetooth" {...props}></Icon>
