<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojapn6a8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ojapn6a8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:information-desk-customer-solid" {...props}></Icon>
