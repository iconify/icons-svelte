<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft-3lt0tv.css';
import '../../css/n/neh-dob8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft-3lt0tv"/><path class="neh-dob8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paint-brush-bold-duotone" {...props}></Icon>
