<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkvx_ob1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xkvx_ob1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hand-heart-filled" {...props}></Icon>
