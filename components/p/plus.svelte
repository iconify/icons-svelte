<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x296-cbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x296-cbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:plus" {...props}></Icon>
