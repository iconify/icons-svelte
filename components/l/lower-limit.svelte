<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf7qtd1bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nf7qtd1bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:lower-limit" {...props}></Icon>
