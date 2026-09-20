<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oni9b4b9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oni9b4b9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:label-filled" {...props}></Icon>
