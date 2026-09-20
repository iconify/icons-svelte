<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhrcuq10c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhrcuq10c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:camera-filled" {...props}></Icon>
