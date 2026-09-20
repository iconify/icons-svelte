<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtmsfsbcp.css';
import '../../css/e/e041-1bai.css';
import '../../css/e/eika0rrpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="jtmsfsbcp"/><circle class="e041-1bai"/><circle class="eika0rrpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:more-alt" {...props}></Icon>
