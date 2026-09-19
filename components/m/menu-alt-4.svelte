<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saz4hzcge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="saz4hzcge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:menu-alt-4" {...props}></Icon>
