<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj5_ycbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gj5_ycbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ctk" {...props}></Icon>
