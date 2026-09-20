<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5rr84b6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5rr84b6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:clock-ten-solid" {...props}></Icon>
