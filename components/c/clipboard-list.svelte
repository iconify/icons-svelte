<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyz8y5c5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyz8y5c5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-list" {...props}></Icon>
