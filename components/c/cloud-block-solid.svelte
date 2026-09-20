<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_8yr-b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t_8yr-b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cloud-block-solid" {...props}></Icon>
