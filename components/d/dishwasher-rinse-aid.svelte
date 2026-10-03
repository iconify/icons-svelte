<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5eetpnom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5eetpnom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dishwasher-rinse-aid" {...props}></Icon>
