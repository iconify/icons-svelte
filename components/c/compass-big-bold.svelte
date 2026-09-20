<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr4wvub4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mr4wvub4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:compass-big-bold" {...props}></Icon>
