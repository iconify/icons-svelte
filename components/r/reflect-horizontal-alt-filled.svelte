<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya80we8aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya80we8aj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:reflect-horizontal-alt-filled" {...props}></Icon>
