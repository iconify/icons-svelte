<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia0poz8wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ia0poz8wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:iobroker" {...props}></Icon>
