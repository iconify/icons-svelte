<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-wkm2f6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-wkm2f6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:heavy-showers-line" {...props}></Icon>
