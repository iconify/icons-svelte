<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz4fj2bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz4fj2bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:corner-left-down" {...props}></Icon>
