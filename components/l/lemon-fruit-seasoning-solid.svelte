<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztked6bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ztked6bew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:lemon-fruit-seasoning-solid" {...props}></Icon>
