<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi-9byb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bi-9byb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:point-of-sale-filled" {...props}></Icon>
