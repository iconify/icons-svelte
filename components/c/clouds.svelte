<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efs_2kbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efs_2kbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clouds" {...props}></Icon>
