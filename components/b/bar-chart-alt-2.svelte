<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rew8143lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rew8143lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bar-chart-alt-2" {...props}></Icon>
