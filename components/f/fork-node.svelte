<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lglub4bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lglub4bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:fork-node" {...props}></Icon>
