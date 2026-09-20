<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgt9us2kc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgt9us2kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:chromecast" {...props}></Icon>
