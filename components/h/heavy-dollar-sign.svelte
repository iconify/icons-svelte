<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov0tgp1pd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ov0tgp1pd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:heavy-dollar-sign" {...props}></Icon>
