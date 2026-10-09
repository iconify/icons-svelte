<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzfty7p4v.css';
import '../../css/f/f_lzw-bhd.css';
import '../../css/y/y5vn0krru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nzfty7p4v"/><path class="f_lzw-bhd"/><path class="y5vn0krru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-van-20" {...props}></Icon>
