<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw_skj6xc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cw_skj6xc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:cloud-flat" {...props}></Icon>
