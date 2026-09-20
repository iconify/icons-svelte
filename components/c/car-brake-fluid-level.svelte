<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn5b-ilqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kn5b-ilqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-brake-fluid-level" {...props}></Icon>
