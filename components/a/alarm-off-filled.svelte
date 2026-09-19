<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4zrs3bne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m4zrs3bne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:alarm-off-filled" {...props}></Icon>
