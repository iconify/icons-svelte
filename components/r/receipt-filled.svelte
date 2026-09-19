<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztfup6bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ztfup6bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:receipt-filled" {...props}></Icon>
