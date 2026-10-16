<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl-yfkvrr.css';
import '../../css/p/p7gth1bju.css';
import '../../css/b/bujm-4v9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pl-yfkvrr"/><path class="p7gth1bju"/><path class="bujm-4v9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cam-48" {...props}></Icon>
