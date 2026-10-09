<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frd-8-btx.css';
import '../../css/x/xw7r97bfx.css';
import '../../css/y/y9mg2tbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="frd-8-btx"/><path class="xw7r97bfx"/><path class="y9mg2tbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ppa-signed-48-bold" {...props}></Icon>
