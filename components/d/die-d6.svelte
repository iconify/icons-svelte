<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5d4zmleu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5d4zmleu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:die-d6" {...props}></Icon>
