<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8y8evb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8y8evb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-minus" {...props}></Icon>
