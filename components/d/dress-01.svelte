<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scf128k4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scf128k4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:dress-01" {...props}></Icon>
