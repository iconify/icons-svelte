<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7yuivz8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7yuivz8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:captions-round" {...props}></Icon>
