<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_l042kxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="e_l042kxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:qr-code" {...props}></Icon>
