<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeg19xb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jeg19xb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:minus" {...props}></Icon>
