<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq32xccdr.css';
import '../../css/l/lm5rabblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gq32xccdr"/><path class="lm5rabblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-up-stroke-circle-half-filled" {...props}></Icon>
