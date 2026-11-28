<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m16j0vbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m16j0vbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:microwave-clock" {...props}></Icon>
