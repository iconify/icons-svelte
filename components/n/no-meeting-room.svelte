<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv1xkviab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv1xkviab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:no-meeting-room" {...props}></Icon>
