<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq3j7uixf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="xq3j7uixf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:asterisk" {...props}></Icon>
