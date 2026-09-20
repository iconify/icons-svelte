<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8nvk3bhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8nvk3bhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:diamond" {...props}></Icon>
