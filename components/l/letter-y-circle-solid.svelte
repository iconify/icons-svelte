<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1gl9ibjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1gl9ibjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-y-circle-solid" {...props}></Icon>
