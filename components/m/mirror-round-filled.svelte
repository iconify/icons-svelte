<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otyqlnb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="otyqlnb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mirror-round-filled" {...props}></Icon>
