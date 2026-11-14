<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtaxddpol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtaxddpol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:briefcase-07" {...props}></Icon>
