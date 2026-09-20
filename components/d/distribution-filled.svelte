<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5433x7qc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i5433x7qc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:distribution-filled" {...props}></Icon>
