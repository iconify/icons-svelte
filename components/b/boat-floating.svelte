<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuxte3b-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iuxte3b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:boat-floating" {...props}></Icon>
