<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebi_z2qhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebi_z2qhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:avatar-square" {...props}></Icon>
