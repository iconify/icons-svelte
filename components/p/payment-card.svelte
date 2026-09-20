<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-wqontpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q-wqontpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:payment-card" {...props}></Icon>
