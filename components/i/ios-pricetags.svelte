<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f832m7bua.css';
import '../../css/e/e5rlcgb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f832m7bua"/><path class="e5rlcgb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-pricetags" {...props}></Icon>
