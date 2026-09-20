<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omn_tbces.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omn_tbces"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:robot-2-fill" {...props}></Icon>
