<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxj5tzieu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cxj5tzieu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-code-bold" {...props}></Icon>
