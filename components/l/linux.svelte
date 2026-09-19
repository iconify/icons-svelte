<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqofr63ct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="vqofr63ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:linux" {...props}></Icon>
