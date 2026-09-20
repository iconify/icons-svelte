<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbr-cwb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbr-cwb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:copa-airlines" {...props}></Icon>
