<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v49x2_ycs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v49x2_ycs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:heart-check" {...props}></Icon>
