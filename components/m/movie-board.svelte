<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4sbyjb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l4sbyjb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:movie-board" {...props}></Icon>
