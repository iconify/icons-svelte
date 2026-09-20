<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjvn1nbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sjvn1nbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:recording-tape-2-flat" {...props}></Icon>
