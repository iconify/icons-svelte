<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtpqlxiey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qtpqlxiey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:payment-recieve-7-solid" {...props}></Icon>
