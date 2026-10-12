<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r11vufb2b.css';
import '../../css/w/wzrtz78mz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r11vufb2b"/><path class="wzrtz78mz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:banknote-20-bold" {...props}></Icon>
