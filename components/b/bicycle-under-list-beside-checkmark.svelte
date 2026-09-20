<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejek3_b1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ejek3_b1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bicycle-under-list-beside-checkmark" {...props}></Icon>
