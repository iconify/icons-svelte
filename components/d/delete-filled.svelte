<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v09mmk0wy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v09mmk0wy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:delete-filled" {...props}></Icon>
