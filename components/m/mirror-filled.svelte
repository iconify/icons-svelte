<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1nge984c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m1nge984c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mirror-filled" {...props}></Icon>
