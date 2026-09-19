<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da8z4_zfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="da8z4_zfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:delivery-truck-small-filled" {...props}></Icon>
