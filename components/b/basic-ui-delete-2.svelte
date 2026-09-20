<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k42f7rbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k42f7rbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-ui-delete-2" {...props}></Icon>
