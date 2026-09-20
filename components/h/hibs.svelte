<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgjfpslgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tgjfpslgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hibs" {...props}></Icon>
