<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp-67djaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jp-67djaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:badge-8k-filled" {...props}></Icon>
