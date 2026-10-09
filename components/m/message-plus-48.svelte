<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyrurpboo.css';
import '../../css/v/vmz9b8bgm.css';
import '../../css/j/jjy9cwbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dyrurpboo"/><path class="vmz9b8bgm"/><path class="jjy9cwbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-plus-48" {...props}></Icon>
