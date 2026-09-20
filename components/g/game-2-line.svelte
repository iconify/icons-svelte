<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oly_l9ycs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oly_l9ycs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:game-2-line" {...props}></Icon>
