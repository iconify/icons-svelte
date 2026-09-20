<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv3-5jg-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vv3-5jg-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:remind-filled" {...props}></Icon>
