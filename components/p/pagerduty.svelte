<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khuc_kbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khuc_kbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pagerduty" {...props}></Icon>
