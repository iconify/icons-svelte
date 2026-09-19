<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u06tkfbua.css';
import '../../css/k/ktvtx3m1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u06tkfbua"/><path clip-rule="evenodd" class="ktvtx3m1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:adobe-premiere-solid" {...props}></Icon>
