<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar6ppzbnf.css';
import '../../css/a/av9ufk_wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ar6ppzbnf"/><path class="av9ufk_wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chart-arrow-trending-20" {...props}></Icon>
