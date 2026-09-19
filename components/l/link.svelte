<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn34_cp0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fn34_cp0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:link" {...props}></Icon>
