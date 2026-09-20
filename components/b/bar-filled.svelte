<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3557nbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h3557nbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:bar-filled" {...props}></Icon>
