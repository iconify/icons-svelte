<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6kqtwjhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6kqtwjhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:mail-multiple" {...props}></Icon>
