<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pas7cr1gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pas7cr1gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:airport-plane-flat" {...props}></Icon>
