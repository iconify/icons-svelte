<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz556xbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":680,"height":850};
const content = `<path class="nz556xbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:add-user" {...props}></Icon>
