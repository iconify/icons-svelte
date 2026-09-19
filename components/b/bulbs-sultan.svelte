<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjyou81me.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjyou81me"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulbs-sultan" {...props}></Icon>
