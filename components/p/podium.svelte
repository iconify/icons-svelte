<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp0k_5yna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gp0k_5yna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:podium" {...props}></Icon>
