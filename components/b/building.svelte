<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohhox-d3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohhox-d3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:building" {...props}></Icon>
