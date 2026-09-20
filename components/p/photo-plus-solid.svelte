<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs_pu7psi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hs_pu7psi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:photo-plus-solid" {...props}></Icon>
