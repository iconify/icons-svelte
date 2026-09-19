<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0hi26bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0hi26bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:reolink-842" {...props}></Icon>
