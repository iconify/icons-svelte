<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb8xb_bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pb8xb_bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:inbox-fill-round" {...props}></Icon>
