<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udo-qjbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udo-qjbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:planet-3-broken" {...props}></Icon>
