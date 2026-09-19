<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vowd07ird.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vowd07ird"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:gamecube" {...props}></Icon>
