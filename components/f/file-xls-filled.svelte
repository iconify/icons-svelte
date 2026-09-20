<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opjqw8bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="opjqw8bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-xls-filled" {...props}></Icon>
