<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh4z9dqco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hh4z9dqco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-charging-outline" {...props}></Icon>
