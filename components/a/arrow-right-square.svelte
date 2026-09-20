<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7ytj0iqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7ytj0iqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-right-square" {...props}></Icon>
