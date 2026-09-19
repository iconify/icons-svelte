<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evq328bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="evq328bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-kiss" {...props}></Icon>
