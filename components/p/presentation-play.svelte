<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqm4dwb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqm4dwb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:presentation-play" {...props}></Icon>
