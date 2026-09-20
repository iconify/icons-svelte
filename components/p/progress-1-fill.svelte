<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ticadcbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ticadcbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:progress-1-fill" {...props}></Icon>
