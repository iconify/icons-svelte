<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqgtzq2po.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqgtzq2po"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:biscuit-minus-outline" {...props}></Icon>
