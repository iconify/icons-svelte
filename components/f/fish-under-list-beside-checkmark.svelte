<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azef4rb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="azef4rb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fish-under-list-beside-checkmark" {...props}></Icon>
