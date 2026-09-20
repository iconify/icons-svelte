<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utsv-3-af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="utsv-3-af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:coffee-takeaway-cup-remix" {...props}></Icon>
