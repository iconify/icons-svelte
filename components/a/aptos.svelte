<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x15d_8b-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x15d_8b-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:aptos" {...props}></Icon>
