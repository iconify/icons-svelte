<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdt7z-kws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="kdt7z-kws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:receipt-cross-remix" {...props}></Icon>
