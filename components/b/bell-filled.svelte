<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuz0gyb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kuz0gyb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:bell-filled" {...props}></Icon>
