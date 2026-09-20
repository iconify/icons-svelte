<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdg-0rfov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdg-0rfov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:compact-disc" {...props}></Icon>
