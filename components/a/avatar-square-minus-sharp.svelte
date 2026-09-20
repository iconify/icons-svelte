<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h74p_acgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h74p_acgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:avatar-square-minus-sharp" {...props}></Icon>
