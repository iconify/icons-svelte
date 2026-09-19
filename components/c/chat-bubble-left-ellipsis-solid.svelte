<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv1cfib3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bv1cfib3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chat-bubble-left-ellipsis-solid" {...props}></Icon>
