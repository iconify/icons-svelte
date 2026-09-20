<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yid9b7myf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yid9b7myf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:e3" {...props}></Icon>
