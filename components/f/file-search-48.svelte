<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkov0acma.css';
import '../../css/z/z9g7v-2tg.css';
import '../../css/d/dexi_790w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gkov0acma"/><path class="z9g7v-2tg"/><path class="dexi_790w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-search-48" {...props}></Icon>
