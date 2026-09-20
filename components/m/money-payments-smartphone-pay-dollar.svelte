<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekdmi3b6m.css';
import '../../css/l/l3_41-7cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ekdmi3b6m"/><path class="l3_41-7cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:money-payments-smartphone-pay-dollar" {...props}></Icon>
