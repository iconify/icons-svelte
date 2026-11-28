<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt6_fab0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dt6_fab0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:castle" {...props}></Icon>
