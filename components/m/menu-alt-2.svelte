<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxpmk7qmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vxpmk7qmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:menu-alt-2" {...props}></Icon>
