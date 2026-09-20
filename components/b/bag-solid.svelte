<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrl4dlb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vrl4dlb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:bag-solid" {...props}></Icon>
