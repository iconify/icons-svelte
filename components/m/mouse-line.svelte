<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sia5vytqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sia5vytqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mouse-line" {...props}></Icon>
