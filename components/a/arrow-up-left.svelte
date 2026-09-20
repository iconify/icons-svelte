<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt78ukgqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="xt78ukgqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:arrow-up-left" {...props}></Icon>
