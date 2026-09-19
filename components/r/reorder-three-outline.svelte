<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx6gsqdoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qx6gsqdoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:reorder-three-outline" {...props}></Icon>
