<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in-8debth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="in-8debth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:d-and-d-beyond" {...props}></Icon>
