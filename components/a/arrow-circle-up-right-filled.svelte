<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmqjhwbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmqjhwbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:arrow-circle-up-right-filled" {...props}></Icon>
