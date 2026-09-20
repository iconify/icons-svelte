<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3_wh5byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3_wh5byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:book" {...props}></Icon>
