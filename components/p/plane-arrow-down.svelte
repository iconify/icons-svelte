<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p36hju8wo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p36hju8wo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:plane-arrow-down" {...props}></Icon>
