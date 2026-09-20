<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyo5cbc3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyo5cbc3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:luggage-off" {...props}></Icon>
