<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgdo9jz0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgdo9jz0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:gender-male" {...props}></Icon>
