<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jps5fp-dj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jps5fp-dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:carousel-vertical" {...props}></Icon>
