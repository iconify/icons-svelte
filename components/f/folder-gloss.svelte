<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhw4n-zri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhw4n-zri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder-gloss" {...props}></Icon>
