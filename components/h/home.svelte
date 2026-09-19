<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy0d3pb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hy0d3pb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:home" {...props}></Icon>
