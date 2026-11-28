<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyc0uprxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyc0uprxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:office-building-search" {...props}></Icon>
