<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8md-gbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q8md-gbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:items-grid-small-16" {...props}></Icon>
