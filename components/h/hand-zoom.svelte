<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njjw8aczg.css';
import '../../css/v/vo_ontb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="njjw8aczg"/><path class="vo_ontb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:hand-zoom" {...props}></Icon>
