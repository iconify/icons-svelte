<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6e9n0bgt.css';
import '../../css/q/qcetc5ipd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6e9n0bgt"/><path clip-rule="evenodd" class="qcetc5ipd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:image-down-filled" {...props}></Icon>
