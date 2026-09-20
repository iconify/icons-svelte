<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml4h4gbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml4h4gbtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cloudy-night-rain-filled" {...props}></Icon>
