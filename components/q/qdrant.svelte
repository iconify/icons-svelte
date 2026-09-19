<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6yxyvb3p.css';
import '../../css/l/l32vte6zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6yxyvb3p"/><path class="l32vte6zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:qdrant" {...props}></Icon>
