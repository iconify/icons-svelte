<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jky9q57sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jky9q57sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:plus" {...props}></Icon>
