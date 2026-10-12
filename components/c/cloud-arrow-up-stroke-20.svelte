<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3s1yw0am.css';
import '../../css/h/h0u2-1bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y3s1yw0am"/><path class="h0u2-1bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:cloud-arrow-up-stroke-20" {...props}></Icon>
