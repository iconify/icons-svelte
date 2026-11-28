<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq4uxb9up.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mq4uxb9up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:minimize" {...props}></Icon>
