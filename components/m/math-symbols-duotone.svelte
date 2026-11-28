<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cib79wb5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cib79wb5b primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:math-symbols-duotone" {...props}></Icon>
