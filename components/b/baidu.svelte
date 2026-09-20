<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr-st_b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3,"top":-2};
const content = `<path class="jr-st_b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:baidu" {...props}></Icon>
