<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxm52nb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxm52nb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:equal-approximately-not" {...props}></Icon>
