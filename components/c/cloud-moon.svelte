<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioxgoz4jx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ioxgoz4jx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cloud-moon" {...props}></Icon>
