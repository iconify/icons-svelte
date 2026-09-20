<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dju037ojc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dju037ojc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:p" {...props}></Icon>
