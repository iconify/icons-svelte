<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9q2oebck.css';
import '../../css/g/gnnib_beb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x9q2oebck"/><path clip-rule="evenodd" class="gnnib_beb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-delete-file" {...props}></Icon>
