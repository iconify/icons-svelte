<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2-4v5bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2-4v5bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:crop-3-2" {...props}></Icon>
