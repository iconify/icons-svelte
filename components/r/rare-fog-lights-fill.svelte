<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q55a64brn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q55a64brn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rare-fog-lights-fill" {...props}></Icon>
