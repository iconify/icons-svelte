<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw9y5ibzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fw9y5ibzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:lego" {...props}></Icon>
