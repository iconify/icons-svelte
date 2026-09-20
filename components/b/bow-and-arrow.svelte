<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjt728jjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gjt728jjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:bow-and-arrow" {...props}></Icon>
