<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z20hp9aer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z20hp9aer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:orbit-round" {...props}></Icon>
