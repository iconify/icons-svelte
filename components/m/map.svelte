<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nct5t0b9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nct5t0b9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:map" {...props}></Icon>
