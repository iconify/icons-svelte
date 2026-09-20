<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5iycbcrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b5iycbcrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gas-station-filled" {...props}></Icon>
