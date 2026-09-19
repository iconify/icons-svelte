<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbwrsq0kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbwrsq0kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:dialpad-circle-01" {...props}></Icon>
