<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrzh3gbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrzh3gbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:qualys" {...props}></Icon>
