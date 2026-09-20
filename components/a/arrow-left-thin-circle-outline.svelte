<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbkr8bjbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbkr8bjbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-left-thin-circle-outline" {...props}></Icon>
