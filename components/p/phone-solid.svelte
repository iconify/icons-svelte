<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh4ts9bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yh4ts9bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:phone-solid" {...props}></Icon>
