<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at5nmb45p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="at5nmb45p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:camera-square-filled" {...props}></Icon>
