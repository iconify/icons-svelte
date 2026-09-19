<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi53ahb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi53ahb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulbs-classic" {...props}></Icon>
