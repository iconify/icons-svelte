<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r57lnacnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r57lnacnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:folder-star" {...props}></Icon>
