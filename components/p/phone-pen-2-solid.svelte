<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw4t0zb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yw4t0zb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:phone-pen-2-solid" {...props}></Icon>
