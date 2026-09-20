<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks-k9hb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ks-k9hb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:close" {...props}></Icon>
