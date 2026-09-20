<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3goiveog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n3goiveog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-under-list-beside-checkmark" {...props}></Icon>
