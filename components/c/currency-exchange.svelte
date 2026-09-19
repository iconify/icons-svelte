<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpot68gto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xpot68gto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:currency-exchange" {...props}></Icon>
