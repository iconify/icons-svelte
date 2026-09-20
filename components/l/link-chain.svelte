<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhzuk02qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yhzuk02qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:link-chain" {...props}></Icon>
