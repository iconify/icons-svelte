<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud03u3b6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ud03u3b6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-point-of-sale-plus" {...props}></Icon>
