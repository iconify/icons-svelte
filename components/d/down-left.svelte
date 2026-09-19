<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xizzrhbul.css';
import '../../css/h/h5p4sr09b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xizzrhbul"/><path class="h5p4sr09b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:down-left" {...props}></Icon>
