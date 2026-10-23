<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe2zeeb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fe2zeeb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:pentagon" {...props}></Icon>
