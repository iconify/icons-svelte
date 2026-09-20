<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2rnlverx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2rnlverx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:moonrepo" {...props}></Icon>
