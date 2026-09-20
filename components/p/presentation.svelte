<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyt08dpgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyt08dpgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:presentation" {...props}></Icon>
