<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzd1uqbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzd1uqbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:css3-line" {...props}></Icon>
