<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwgceku3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwgceku3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:projector-2-fill" {...props}></Icon>
