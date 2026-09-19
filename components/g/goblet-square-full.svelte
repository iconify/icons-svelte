<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lycl2fbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lycl2fbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:goblet-square-full" {...props}></Icon>
