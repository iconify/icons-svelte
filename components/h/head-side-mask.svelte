<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lafypubwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lafypubwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:head-side-mask" {...props}></Icon>
