<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kak5-8b1v.css';
import '../../css/y/ylye7u88m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kak5-8b1v"/><path class="ylye7u88m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:line-height-20" {...props}></Icon>
