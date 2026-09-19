<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dalli1b-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dalli1b-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:battery-half" {...props}></Icon>
