<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr88avvfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr88avvfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:refresh-alert" {...props}></Icon>
