<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlqwszbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlqwszbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:key-gloss" {...props}></Icon>
