<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq3zjyb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iq3zjyb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:loaf-of-bread" {...props}></Icon>
