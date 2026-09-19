<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrblk-b2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mrblk-b2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:right-angle" {...props}></Icon>
