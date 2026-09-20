<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agh7bvl2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agh7bvl2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:firebase-fill" {...props}></Icon>
