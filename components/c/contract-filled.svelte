<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z00-s6bfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z00-s6bfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:contract-filled" {...props}></Icon>
