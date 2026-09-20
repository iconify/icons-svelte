<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r54-3ccgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r54-3ccgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:earth-filled" {...props}></Icon>
