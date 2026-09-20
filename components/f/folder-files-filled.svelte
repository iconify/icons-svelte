<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz00br_eb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pz00br_eb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:folder-files-filled" {...props}></Icon>
