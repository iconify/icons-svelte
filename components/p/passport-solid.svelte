<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlrsj2b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qlrsj2b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:passport-solid" {...props}></Icon>
