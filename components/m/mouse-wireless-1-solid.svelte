<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyk557rsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pyk557rsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:mouse-wireless-1-solid" {...props}></Icon>
