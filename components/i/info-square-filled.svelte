<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnenm3buo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xnenm3buo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:info-square-filled" {...props}></Icon>
