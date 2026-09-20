<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya3dkm1ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya3dkm1ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:abacus-off" {...props}></Icon>
