<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4_frccvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4_frccvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:presentation-check" {...props}></Icon>
