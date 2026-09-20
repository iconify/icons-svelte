<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etnxx7kib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="etnxx7kib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ascending-number-order-solid" {...props}></Icon>
