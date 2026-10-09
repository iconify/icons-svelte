<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhl8dp5hn.css';
import '../../css/n/nb9mp9bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zhl8dp5hn"/><path class="nb9mp9bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-left-to-line-20" {...props}></Icon>
