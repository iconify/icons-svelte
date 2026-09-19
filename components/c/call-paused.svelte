<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb9xl5bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb9xl5bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:call-paused" {...props}></Icon>
