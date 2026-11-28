<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee58kac0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee58kac0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:map-pin-check" {...props}></Icon>
