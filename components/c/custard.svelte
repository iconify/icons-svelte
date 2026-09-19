<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4ix4_bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l4ix4_bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:custard" {...props}></Icon>
