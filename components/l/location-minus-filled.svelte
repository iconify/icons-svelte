<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slq3vpbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slq3vpbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:location-minus-filled" {...props}></Icon>
