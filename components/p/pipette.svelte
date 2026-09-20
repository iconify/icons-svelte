<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwgeb1ihr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwgeb1ihr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pipette" {...props}></Icon>
