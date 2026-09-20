<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw2-p-bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bw2-p-bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:columns-4" {...props}></Icon>
