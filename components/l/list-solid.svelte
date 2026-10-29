<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhv89ymdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhv89ymdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:list-solid" {...props}></Icon>
