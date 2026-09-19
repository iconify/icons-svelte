<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm13dtb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xm13dtb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:document-plus" {...props}></Icon>
