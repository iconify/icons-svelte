<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x07qj48-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x07qj48-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:login-1-solid" {...props}></Icon>
