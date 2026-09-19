<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4b_gir2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":339,"height":720};
const content = `<path class="g4b_gir2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:female" {...props}></Icon>
