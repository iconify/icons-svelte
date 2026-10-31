<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxp4o7b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxp4o7b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:presentation-round" {...props}></Icon>
