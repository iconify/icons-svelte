<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lojnqnl8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lojnqnl8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:people-sleeping-in-bunkbeds-in-eaved-leanto-shelter" {...props}></Icon>
