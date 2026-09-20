<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a28g7xbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="a28g7xbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:pie-chart" {...props}></Icon>
