<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijt2-hgvq.css';
import '../../css/l/lojifgbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="ijt2-hgvq"/><path class="lojifgbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:png" {...props}></Icon>
