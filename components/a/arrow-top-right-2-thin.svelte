<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofi3dj95o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofi3dj95o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-right-2-thin" {...props}></Icon>
