<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m10j8gbgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m10j8gbgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:link-plus" {...props}></Icon>
