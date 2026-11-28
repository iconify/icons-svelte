<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0xvr4gta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary z0xvr4gta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mouse-pointer-duotone" {...props}></Icon>
