<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-bc1ybft.css';
import '../../css/f/f5keg8bhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f-bc1ybft"/><path class="f5keg8bhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-20" {...props}></Icon>
