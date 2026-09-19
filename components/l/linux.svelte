<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebj6rvb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="ebj6rvb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:linux" {...props}></Icon>
