<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hup2v_9xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hup2v_9xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:notes-multiple" {...props}></Icon>
