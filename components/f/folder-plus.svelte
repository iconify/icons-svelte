<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4r4kjkia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x4r4kjkia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:folder-plus" {...props}></Icon>
