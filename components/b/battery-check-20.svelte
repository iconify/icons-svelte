<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6b3i8cls.css';
import '../../css/x/xgcr5txor.css';
import '../../css/m/mg--uz6gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f6b3i8cls"/><path class="xgcr5txor"/><path class="mg--uz6gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-check-20" {...props}></Icon>
