<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tisl7lofk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tisl7lofk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:board-bus" {...props}></Icon>
