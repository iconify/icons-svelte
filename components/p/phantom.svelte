<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrza40bty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrza40bty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:phantom" {...props}></Icon>
