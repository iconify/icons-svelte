<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-d5f3oms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-d5f3oms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:books-minus" {...props}></Icon>
