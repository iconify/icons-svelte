<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nixyq4bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nixyq4bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bubble-text" {...props}></Icon>
