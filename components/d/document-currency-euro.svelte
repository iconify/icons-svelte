<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgx19ns4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgx19ns4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-currency-euro" {...props}></Icon>
