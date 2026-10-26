<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btc2bc1ol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="btc2bc1ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:fire" {...props}></Icon>
