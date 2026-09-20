<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzhlgjbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzhlgjbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:campaign-monitor-logo" {...props}></Icon>
