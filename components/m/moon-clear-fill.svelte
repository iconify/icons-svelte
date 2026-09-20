<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we4cfybou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="we4cfybou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:moon-clear-fill" {...props}></Icon>
