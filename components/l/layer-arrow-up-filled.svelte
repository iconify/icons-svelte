<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufxbcneuu.css';
import '../../css/h/h2vtajpsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufxbcneuu"/><path class="h2vtajpsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:layer-arrow-up-filled" {...props}></Icon>
