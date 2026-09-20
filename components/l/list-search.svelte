<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl8j6cbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sl8j6cbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:list-search" {...props}></Icon>
