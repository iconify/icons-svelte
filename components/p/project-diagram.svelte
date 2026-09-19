<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3hwew7vt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="n3hwew7vt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:project-diagram" {...props}></Icon>
