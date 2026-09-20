<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nor0fwmgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="nor0fwmgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:previous-step-2" {...props}></Icon>
