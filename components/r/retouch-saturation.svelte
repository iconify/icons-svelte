<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw7ruzy2e.css';
import '../../css/a/ay63a2o9s.css';
import '../../css/n/nqlosb-6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw7ruzy2e"/><path class="ay63a2o9s"/><path class="nqlosb-6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:retouch-saturation" {...props}></Icon>
