<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_sm72a9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c_sm72a9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:assembly-riscv" {...props}></Icon>
