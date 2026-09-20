<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhga7b2ch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhga7b2ch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:heat-pump" {...props}></Icon>
