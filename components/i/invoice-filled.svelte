<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xac5i9bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xac5i9bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:invoice-filled" {...props}></Icon>
