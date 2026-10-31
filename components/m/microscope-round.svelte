<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4rwlkb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4rwlkb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:microscope-round" {...props}></Icon>
