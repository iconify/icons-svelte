<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvr6yacwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvr6yacwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:instagram-logotype" {...props}></Icon>
