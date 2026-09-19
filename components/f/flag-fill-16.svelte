<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thk55vbks.css';
import '../../css/o/o6e3x-bef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="thk55vbks"/><path class="o6e3x-bef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:flag-fill-16" {...props}></Icon>
