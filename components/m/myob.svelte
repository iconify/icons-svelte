<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwnt3j9zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwnt3j9zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:myob" {...props}></Icon>
