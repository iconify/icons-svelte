<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fop36ybmj.css';
import '../../css/v/vpxwfc0bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fop36ybmj"/><path class="vpxwfc0bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-range-48-bold" {...props}></Icon>
