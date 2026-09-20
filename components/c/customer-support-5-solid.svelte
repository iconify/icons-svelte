<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii30u3bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ii30u3bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:customer-support-5-solid" {...props}></Icon>
