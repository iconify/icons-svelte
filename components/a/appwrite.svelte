<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/macbe7bdm.css';
import '../../css/l/lw3w-bciy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="macbe7bdm"/><path class="lw3w-bciy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:appwrite" {...props}></Icon>
