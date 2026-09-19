<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whlv7ub9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whlv7ub9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:outside" {...props}></Icon>
