<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbb_tgbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cbb_tgbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:inbox" {...props}></Icon>
