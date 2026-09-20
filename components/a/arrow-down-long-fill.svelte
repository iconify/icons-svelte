<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jskqlbpwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jskqlbpwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-down-long-fill" {...props}></Icon>
