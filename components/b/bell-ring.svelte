<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3vr93bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3vr93bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bell-ring" {...props}></Icon>
