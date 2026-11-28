<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdj9x2b-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdj9x2b-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:outlet-solid" {...props}></Icon>
