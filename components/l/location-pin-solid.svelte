<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-e3s_b-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-e3s_b-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:location-pin-solid" {...props}></Icon>
