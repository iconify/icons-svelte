<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do3f0-lqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="do3f0-lqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:pagerduty" {...props}></Icon>
