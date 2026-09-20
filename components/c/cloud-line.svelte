<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j82ljlhri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j82ljlhri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:cloud-line" {...props}></Icon>
