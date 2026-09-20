<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9th1mpie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x9th1mpie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:percent-filled" {...props}></Icon>
