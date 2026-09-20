<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at-b72jsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="at-b72jsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:haze-fill" {...props}></Icon>
