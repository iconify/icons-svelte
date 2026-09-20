<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0sk24kwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0sk24kwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-90" {...props}></Icon>
