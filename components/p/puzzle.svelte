<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs65zonnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="gs65zonnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:puzzle" {...props}></Icon>
