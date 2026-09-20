<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic9-wxsjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ic9-wxsjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:lounging" {...props}></Icon>
