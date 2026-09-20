<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osv1b-n0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="osv1b-n0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lift-gate" {...props}></Icon>
