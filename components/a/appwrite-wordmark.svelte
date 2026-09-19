<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzlt8abim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hzlt8abim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:appwrite-wordmark" {...props}></Icon>
