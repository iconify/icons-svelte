<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai5y9abrj.css';
import '../../css/t/t5wv3ubfi.css';
import '../../css/v/vlejwkz4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="ai5y9abrj"/><path class="t5wv3ubfi"/><path class="vlejwkz4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:mongolia" {...props}></Icon>
