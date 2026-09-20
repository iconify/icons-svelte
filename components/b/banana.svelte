<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su3hmfhdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="su3hmfhdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:banana" {...props}></Icon>
