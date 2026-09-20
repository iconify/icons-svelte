<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbs9qlb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbs9qlb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:arrow-left" {...props}></Icon>
