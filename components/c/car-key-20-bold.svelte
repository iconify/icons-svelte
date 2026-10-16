<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2ezievuu.css';
import '../../css/h/h0hx-t7ds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v2ezievuu"/><path class="h0hx-t7ds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:car-key-20-bold" {...props}></Icon>
