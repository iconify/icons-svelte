<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tliyki-wu.css';
import '../../css/s/s70ezsbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tliyki-wu"/><path class="s70ezsbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:image-copy" {...props}></Icon>
