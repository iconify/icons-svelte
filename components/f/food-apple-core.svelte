<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aza5olbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aza5olbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:food-apple-core" {...props}></Icon>
