<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhc643b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhc643b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:aspect-ratio-fill" {...props}></Icon>
