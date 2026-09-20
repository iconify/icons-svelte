<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv5ee7d2i.css';
import '../../css/j/jdm0z2b0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lv5ee7d2i"/><path class="jdm0z2b0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:reduce-16" {...props}></Icon>
