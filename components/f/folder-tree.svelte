<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u00ue5b6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="u00ue5b6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:folder-tree" {...props}></Icon>
