<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulnbhdcuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ulnbhdcuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-arrow-down-filled" {...props}></Icon>
