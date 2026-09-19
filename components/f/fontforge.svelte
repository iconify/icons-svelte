<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crspx5bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":450,"height":512};
const content = `<path class="crspx5bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:fontforge" {...props}></Icon>
