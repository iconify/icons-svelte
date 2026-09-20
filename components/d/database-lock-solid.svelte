<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7ype5bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n7ype5bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:database-lock-solid" {...props}></Icon>
