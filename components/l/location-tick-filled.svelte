<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoayuz9iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zoayuz9iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:location-tick-filled" {...props}></Icon>
