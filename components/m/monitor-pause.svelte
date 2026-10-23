<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3w2iwjtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3w2iwjtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:monitor-pause" {...props}></Icon>
