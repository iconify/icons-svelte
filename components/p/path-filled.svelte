<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5wps6zzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r5wps6zzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:path-filled" {...props}></Icon>
