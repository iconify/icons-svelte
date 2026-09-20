<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le0i-4b7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="le0i-4b7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:paperclip-2-flat" {...props}></Icon>
