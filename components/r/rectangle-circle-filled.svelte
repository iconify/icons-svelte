<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvo1z902s.css';
import '../../css/p/p7s3evb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tvo1z902s"/><path class="p7s3evb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:rectangle-circle-filled" {...props}></Icon>
