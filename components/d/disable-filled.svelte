<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzcjc9-6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yzcjc9-6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:disable-filled" {...props}></Icon>
