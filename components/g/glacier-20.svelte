<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prpf4nbyc.css';
import '../../css/c/cvgo0ielg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="prpf4nbyc"/><path class="cvgo0ielg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:glacier-20" {...props}></Icon>
