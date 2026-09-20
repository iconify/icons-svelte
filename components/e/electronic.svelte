<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb1jiicvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lb1jiicvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:electronic" {...props}></Icon>
