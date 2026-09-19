<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nre9ogsov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nre9ogsov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-h1-2" {...props}></Icon>
