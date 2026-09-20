<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft9ws6bod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft9ws6bod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:liquid" {...props}></Icon>
