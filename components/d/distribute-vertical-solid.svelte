<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvy2h7vyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xvy2h7vyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:distribute-vertical-solid" {...props}></Icon>
