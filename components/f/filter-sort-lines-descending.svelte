<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlkp8c8fe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlkp8c8fe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:filter-sort-lines-descending" {...props}></Icon>
