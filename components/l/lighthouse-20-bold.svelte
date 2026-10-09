<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umeximbue.css';
import '../../css/z/zyqw81bux.css';
import '../../css/r/r98z67v2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="umeximbue"/><path class="zyqw81bux"/><path class="r98z67v2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lighthouse-20-bold" {...props}></Icon>
