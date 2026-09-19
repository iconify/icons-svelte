<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br9gtx66z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="br9gtx66z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:keyboard-filled" {...props}></Icon>
