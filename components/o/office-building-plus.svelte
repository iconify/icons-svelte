<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j96zg6bjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j96zg6bjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:office-building-plus" {...props}></Icon>
