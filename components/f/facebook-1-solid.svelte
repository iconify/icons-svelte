<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3cwk-ews.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="n3cwk-ews"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:facebook-1-solid" {...props}></Icon>
