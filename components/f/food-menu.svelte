<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/niijr9bav.css';
import '../../css/p/pv8augtve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="niijr9bav"/><path class="pv8augtve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:food-menu" {...props}></Icon>
