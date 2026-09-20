<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx4zlylhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rx4zlylhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:alert-fill" {...props}></Icon>
