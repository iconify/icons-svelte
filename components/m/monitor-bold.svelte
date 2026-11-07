<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz52zxbce.css';
import '../../css/l/ld9e7wt3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vz52zxbce"/><path class="ld9e7wt3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:monitor-bold" {...props}></Icon>
