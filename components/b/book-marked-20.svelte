<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ils33xbkf.css';
import '../../css/m/mv-f1_b6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ils33xbkf"/><path class="mv-f1_b6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:book-marked-20" {...props}></Icon>
