<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb42m0bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lb42m0bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cloud-share-remix" {...props}></Icon>
