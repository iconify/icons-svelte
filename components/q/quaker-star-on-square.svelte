<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0-jzjbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g0-jzjbzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:quaker-star-on-square" {...props}></Icon>
