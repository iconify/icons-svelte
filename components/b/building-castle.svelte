<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j00fx8bzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j00fx8bzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:building-castle" {...props}></Icon>
