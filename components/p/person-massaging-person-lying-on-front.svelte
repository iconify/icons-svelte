<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnac4ibum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vnac4ibum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-massaging-person-lying-on-front" {...props}></Icon>
