<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhshecbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhshecbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layout-dashboard-solid" {...props}></Icon>
