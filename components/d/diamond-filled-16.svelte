<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9a-29sdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y9a-29sdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:diamond-filled-16" {...props}></Icon>
