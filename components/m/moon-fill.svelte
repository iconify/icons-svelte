<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt5q8rs1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt5q8rs1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:moon-fill" {...props}></Icon>
