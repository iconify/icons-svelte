<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdhcrkpde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdhcrkpde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:location-question-outline" {...props}></Icon>
