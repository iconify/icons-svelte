<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn2wf5bnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dn2wf5bnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:danger" {...props}></Icon>
