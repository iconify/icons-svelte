<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzbmkwk2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzbmkwk2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:crop-free" {...props}></Icon>
