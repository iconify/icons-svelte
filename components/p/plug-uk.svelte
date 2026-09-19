<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8c_s2h5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8c_s2h5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:plug-uk" {...props}></Icon>
