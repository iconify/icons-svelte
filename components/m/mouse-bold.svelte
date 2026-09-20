<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j18rfhbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j18rfhbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mouse-bold" {...props}></Icon>
