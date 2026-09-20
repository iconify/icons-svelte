<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqosobbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqosobbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dumbbell-linear" {...props}></Icon>
