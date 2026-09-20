<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boe6k9bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="boe6k9bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clock-hour-7-filled" {...props}></Icon>
