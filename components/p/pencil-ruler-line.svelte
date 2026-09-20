<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jalnjobfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jalnjobfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pencil-ruler-line" {...props}></Icon>
