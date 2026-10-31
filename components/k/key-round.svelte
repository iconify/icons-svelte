<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i16a3oyiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i16a3oyiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:key-round" {...props}></Icon>
