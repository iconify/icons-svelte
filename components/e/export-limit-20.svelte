<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io2eiemnh.css';
import '../../css/u/uxhgw2beg.css';
import '../../css/w/weytrjnhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="io2eiemnh"/><path class="uxhgw2beg"/><path class="weytrjnhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:export-limit-20" {...props}></Icon>
