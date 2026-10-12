<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib2oze94a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ib2oze94a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bell-ring-filled" {...props}></Icon>
