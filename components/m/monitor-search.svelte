<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glh1rubhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glh1rubhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:monitor-search" {...props}></Icon>
