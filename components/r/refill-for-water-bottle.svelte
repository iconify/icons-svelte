<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjud3gb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjud3gb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:refill-for-water-bottle" {...props}></Icon>
