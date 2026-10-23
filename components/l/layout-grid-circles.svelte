<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc14tkbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc14tkbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:layout-grid-circles" {...props}></Icon>
