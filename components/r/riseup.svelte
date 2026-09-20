<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzw4rrtho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzw4rrtho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:riseup" {...props}></Icon>
