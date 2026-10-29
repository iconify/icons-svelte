<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx4hv3bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mx4hv3bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:play-off" {...props}></Icon>
