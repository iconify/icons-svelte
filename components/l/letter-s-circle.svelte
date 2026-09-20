<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9rv8y8ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9rv8y8ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-s-circle" {...props}></Icon>
