<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-hicubhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g-hicubhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:airport-plane-solid" {...props}></Icon>
