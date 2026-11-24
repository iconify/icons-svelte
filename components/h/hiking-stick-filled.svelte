<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqiaa8e-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sqiaa8e-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hiking-stick-filled" {...props}></Icon>
