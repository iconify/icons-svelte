<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnnx2lbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wnnx2lbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:arrow-diagonal-2-flat" {...props}></Icon>
