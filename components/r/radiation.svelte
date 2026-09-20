<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g39vi6b0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g39vi6b0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:radiation" {...props}></Icon>
