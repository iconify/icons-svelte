<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnp67f2po.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xnp67f2po"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:paint-bucket-16" {...props}></Icon>
