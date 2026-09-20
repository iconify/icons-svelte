<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-4tdoufz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-4tdoufz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-u-square-solid" {...props}></Icon>
