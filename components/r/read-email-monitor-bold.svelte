<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km7s_km6t.css';
import '../../css/y/ygu8evkrm.css';
import '../../css/d/dzn4brbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km7s_km6t"/><path class="ygu8evkrm"/><path class="dzn4brbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:read-email-monitor-bold" {...props}></Icon>
