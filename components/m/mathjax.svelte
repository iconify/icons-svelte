<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0fd-kbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="s0fd-kbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:mathjax" {...props}></Icon>
