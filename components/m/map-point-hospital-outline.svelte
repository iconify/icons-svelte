<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onb0tacme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="onb0tacme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-point-hospital-outline" {...props}></Icon>
