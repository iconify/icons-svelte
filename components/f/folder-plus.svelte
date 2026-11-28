<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tgy8uab8v.css';
import '../../css/f/f-kk1tocm.css';
import '../../css/v/vmi2_9iax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="tgy8uab8v"/><path class="f-kk1tocm"/><path class="vmi2_9iax"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-plus" {...props}></Icon>
