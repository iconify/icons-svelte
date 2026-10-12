<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-x5p8uzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p-x5p8uzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:cloud-arrow-up-fill-20" {...props}></Icon>
