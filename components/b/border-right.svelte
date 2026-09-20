<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhxmexbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhxmexbtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:border-right" {...props}></Icon>
