<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njaw6lxwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njaw6lxwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alert-octagram-outline" {...props}></Icon>
