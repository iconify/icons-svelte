<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0lp7qnap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0lp7qnap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:riding-fill" {...props}></Icon>
