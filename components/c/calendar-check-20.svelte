<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-bc1ybft.css';
import '../../css/a/a394r9b2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f-bc1ybft"/><path class="a394r9b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-check-20" {...props}></Icon>
