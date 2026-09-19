<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lisuk0b5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lisuk0b5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-general-group" {...props}></Icon>
