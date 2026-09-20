<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2etimw2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2etimw2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:keyboard-box-line" {...props}></Icon>
