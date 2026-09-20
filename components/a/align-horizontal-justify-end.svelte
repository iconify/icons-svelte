<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-cegabsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-cegabsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:align-horizontal-justify-end" {...props}></Icon>
