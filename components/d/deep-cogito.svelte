<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gaeskvbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gaeskvbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:deep-cogito" {...props}></Icon>
