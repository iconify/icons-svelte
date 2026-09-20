<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0rt58u6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0rt58u6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:grid3" {...props}></Icon>
