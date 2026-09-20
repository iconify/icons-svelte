<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie9yf-1hu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie9yf-1hu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:plane" {...props}></Icon>
