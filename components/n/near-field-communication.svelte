<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss7xuob1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ss7xuob1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:near-field-communication" {...props}></Icon>
