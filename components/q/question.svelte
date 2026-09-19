<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmdxg1bgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":24};
const content = `<path class="tmdxg1bgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:question" {...props}></Icon>
