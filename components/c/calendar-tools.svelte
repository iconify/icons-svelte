<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfsv8v-qt.css';
import '../../css/t/teb2t72mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yfsv8v-qt"/><path class="teb2t72mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:calendar-tools" {...props}></Icon>
