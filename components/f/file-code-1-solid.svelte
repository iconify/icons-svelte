<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-x1i7szn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s-x1i7szn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:file-code-1-solid" {...props}></Icon>
