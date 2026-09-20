<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw6l6rbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw6l6rbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-imac-minus" {...props}></Icon>
