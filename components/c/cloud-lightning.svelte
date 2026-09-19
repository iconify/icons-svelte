<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv8dteuwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jv8dteuwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cloud-lightning" {...props}></Icon>
