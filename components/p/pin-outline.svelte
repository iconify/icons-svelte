<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzdt_tbkb.css';
import '../../css/u/uh6i7ubar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzdt_tbkb"/><path class="uh6i7ubar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:pin-outline" {...props}></Icon>
