<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh4g_ac8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh4g_ac8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mail-badge" {...props}></Icon>
