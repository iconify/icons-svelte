<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1gi4uztp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1gi4uztp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:cloud-filled" {...props}></Icon>
