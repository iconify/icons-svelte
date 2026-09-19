<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gaxcgtbkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="gaxcgtbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:chat-bubble-bottom-center" {...props}></Icon>
