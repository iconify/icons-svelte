<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_xjfiztf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":961,"height":1024};
const content = `<path class="h_xjfiztf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:piano" {...props}></Icon>
