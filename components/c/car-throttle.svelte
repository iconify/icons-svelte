<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da_ij5bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="da_ij5bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:car-throttle" {...props}></Icon>
