<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr36w-16i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mr36w-16i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:heart-pulse-filled" {...props}></Icon>
