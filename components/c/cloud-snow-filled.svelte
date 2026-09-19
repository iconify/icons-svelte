<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/biu392k5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="biu392k5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cloud-snow-filled" {...props}></Icon>
