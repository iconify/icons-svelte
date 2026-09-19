<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoc17ipvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zoc17ipvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:close-circle-outline" {...props}></Icon>
