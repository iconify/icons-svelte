<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hghe9jjov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hghe9jjov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-sparkle-fill-round" {...props}></Icon>
