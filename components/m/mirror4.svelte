<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4u691ylc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4u691ylc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mirror4" {...props}></Icon>
