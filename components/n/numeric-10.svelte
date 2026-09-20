<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rik9ss2_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rik9ss2_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-10" {...props}></Icon>
