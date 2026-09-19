<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct6yfj32v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ct6yfj32v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:joints-outline-24px" {...props}></Icon>
