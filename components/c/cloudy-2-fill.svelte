<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_mh1h_-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_mh1h_-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:cloudy-2-fill" {...props}></Icon>
