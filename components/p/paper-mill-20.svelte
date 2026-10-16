<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7dkymbhs.css';
import '../../css/s/sa1-qxbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i7dkymbhs"/><path class="sa1-qxbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paper-mill-20" {...props}></Icon>
