<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uagmrhiax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uagmrhiax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:human-male-height" {...props}></Icon>
