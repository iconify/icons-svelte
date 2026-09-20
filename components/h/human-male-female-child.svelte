<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0nf37xkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0nf37xkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:human-male-female-child" {...props}></Icon>
