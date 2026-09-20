<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-g771bwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a-g771bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:github-release-monitor-light" {...props}></Icon>
