<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt1axk4rz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gt1axk4rz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:power" {...props}></Icon>
