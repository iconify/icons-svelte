<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4u4mbc3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":65,"height":64};
const content = `<path class="q4u4mbc3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:alternative-complementary" {...props}></Icon>
