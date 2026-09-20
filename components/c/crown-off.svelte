<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td245dbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td245dbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:crown-off" {...props}></Icon>
