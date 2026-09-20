<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjd8obcdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xjd8obcdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:airport-15" {...props}></Icon>
