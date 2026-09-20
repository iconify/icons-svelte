<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpu6mrbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rpu6mrbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:aerial-lift-filled" {...props}></Icon>
