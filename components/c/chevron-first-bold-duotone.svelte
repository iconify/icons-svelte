<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/raun3xbhc.css';
import '../../css/d/dk3eigbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="raun3xbhc"/><path class="dk3eigbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevron-first-bold-duotone" {...props}></Icon>
