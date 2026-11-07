<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl-h9o8md.css';
import '../../css/e/eclqm_bbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl-h9o8md"/><path class="eclqm_bbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-left-to-line-bold-duotone" {...props}></Icon>
