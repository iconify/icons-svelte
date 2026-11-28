<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faebr949z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="faebr949z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:circle-4" {...props}></Icon>
