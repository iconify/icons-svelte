<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfdrazgdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nfdrazgdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:barbecue-grill-wheeled-with-steam" {...props}></Icon>
