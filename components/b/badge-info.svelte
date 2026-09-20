<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5q0twbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5q0twbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:badge-info" {...props}></Icon>
