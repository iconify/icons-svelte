<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izwngpo4z.css';
import '../../css/w/w8fd4ubay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="izwngpo4z"/><path class="w8fd4ubay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:plurk" {...props}></Icon>
