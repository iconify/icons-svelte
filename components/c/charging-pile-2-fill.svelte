<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwm9cd21b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwm9cd21b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:charging-pile-2-fill" {...props}></Icon>
