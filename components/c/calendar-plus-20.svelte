<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-bc1ybft.css';
import '../../css/a/a99zzxb0t.css';
import '../../css/f/fp91mvbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f-bc1ybft"/><path class="a99zzxb0t"/><path class="fp91mvbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-plus-20" {...props}></Icon>
