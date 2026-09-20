<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktgsm8eun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktgsm8eun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:aas-project-tia" {...props}></Icon>
