<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfb3x1bkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfb3x1bkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-sync" {...props}></Icon>
