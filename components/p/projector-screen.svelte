<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d35yl_bae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d35yl_bae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:projector-screen" {...props}></Icon>
