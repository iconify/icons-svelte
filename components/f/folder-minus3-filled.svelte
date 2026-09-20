<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z77c00bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z77c00bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:folder-minus3-filled" {...props}></Icon>
