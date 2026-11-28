<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypwpt66ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypwpt66ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:gate-xor-solid" {...props}></Icon>
