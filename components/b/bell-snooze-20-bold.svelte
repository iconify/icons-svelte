<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6vbh3spu.css';
import '../../css/k/kwnn45cyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d6vbh3spu"/><path class="kwnn45cyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bell-snooze-20-bold" {...props}></Icon>
