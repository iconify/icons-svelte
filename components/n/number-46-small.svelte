<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmxwfq3ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmxwfq3ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-46-small" {...props}></Icon>
