<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m816b_h6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m816b_h6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:adobe-solid" {...props}></Icon>
