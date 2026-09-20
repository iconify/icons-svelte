<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwtsf1bcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pwtsf1bcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hierarchy-2-solid" {...props}></Icon>
