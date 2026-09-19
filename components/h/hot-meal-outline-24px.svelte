<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m33awjb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m33awjb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:hot-meal-outline-24px" {...props}></Icon>
