<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fevon8ayl.css';
import '../../css/z/z9t-ptwsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fevon8ayl"/><path class="z9t-ptwsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-arrow-up-bold-duotone" {...props}></Icon>
