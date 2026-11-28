<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouj2rlbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ouj2rlbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:gem-star" {...props}></Icon>
