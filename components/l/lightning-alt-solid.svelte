<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt2dw8m3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zt2dw8m3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:lightning-alt-solid" {...props}></Icon>
