<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2d9xbigc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2d9xbigc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:fold-vertical" {...props}></Icon>
