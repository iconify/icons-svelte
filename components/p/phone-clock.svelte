<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eik6_sx3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eik6_sx3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:phone-clock" {...props}></Icon>
