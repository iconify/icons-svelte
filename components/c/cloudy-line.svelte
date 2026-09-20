<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suwzxkbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="suwzxkbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:cloudy-line" {...props}></Icon>
