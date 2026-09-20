<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlpuqyboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlpuqyboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:muo" {...props}></Icon>
