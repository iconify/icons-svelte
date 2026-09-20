<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szjyx1f0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szjyx1f0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:apps" {...props}></Icon>
