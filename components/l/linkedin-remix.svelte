<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n44p__bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n44p__bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:linkedin-remix" {...props}></Icon>
