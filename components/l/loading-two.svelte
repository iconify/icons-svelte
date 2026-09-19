<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k179mzbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k179mzbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:loading-two" {...props}></Icon>
