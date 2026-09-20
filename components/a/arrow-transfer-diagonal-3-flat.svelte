<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6yo07bnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n6yo07bnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-transfer-diagonal-3-flat" {...props}></Icon>
