<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc4zhgevm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mc4zhgevm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-linear" {...props}></Icon>
