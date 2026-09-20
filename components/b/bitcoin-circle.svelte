<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glvt67bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="glvt67bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:bitcoin-circle" {...props}></Icon>
