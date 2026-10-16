<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxzebdb5x.css';
import '../../css/r/ro3ticcmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yxzebdb5x"/><path class="ro3ticcmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folders-48-bold" {...props}></Icon>
