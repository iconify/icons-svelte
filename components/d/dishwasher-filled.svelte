<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjk_cab6w.css';
import '../../css/p/po-pxqb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjk_cab6w"/><path class="po-pxqb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dishwasher-filled" {...props}></Icon>
