<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi3a7acyt.css';
import '../../css/b/bjedjv8iv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi3a7acyt"/><path class="bjedjv8iv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:newspaper" {...props}></Icon>
