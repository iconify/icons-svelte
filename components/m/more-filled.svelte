<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emnj4mg-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="emnj4mg-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:more-filled" {...props}></Icon>
