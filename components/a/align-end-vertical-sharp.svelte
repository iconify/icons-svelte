<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msh-i_byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msh-i_byo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-end-vertical-sharp" {...props}></Icon>
