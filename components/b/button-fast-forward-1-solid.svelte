<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuv56d10r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vuv56d10r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:button-fast-forward-1-solid" {...props}></Icon>
