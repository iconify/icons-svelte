<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-_303-2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-_303-2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:leaf" {...props}></Icon>
