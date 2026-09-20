<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1a67jbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v1a67jbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:folder-filled" {...props}></Icon>
