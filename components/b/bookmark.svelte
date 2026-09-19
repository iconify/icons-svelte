<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioh0fbcui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ioh0fbcui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bookmark" {...props}></Icon>
