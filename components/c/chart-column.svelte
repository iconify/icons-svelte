<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkg5wobjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkg5wobjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chart-column" {...props}></Icon>
