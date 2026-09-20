<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je_6zsb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="je_6zsb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-battery" {...props}></Icon>
