<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax68hvg5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax68hvg5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:robot-vacuum" {...props}></Icon>
