<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okjc2gbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okjc2gbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:home-search" {...props}></Icon>
