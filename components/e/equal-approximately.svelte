<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-qm7acrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-qm7acrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:equal-approximately" {...props}></Icon>
