<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf59cilyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yf59cilyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:label-off-filled" {...props}></Icon>
