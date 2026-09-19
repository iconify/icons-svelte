<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3m2iv_dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3m2iv_dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:battery-temp" {...props}></Icon>
