<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn3ddwbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yn3ddwbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:dental-off" {...props}></Icon>
