<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmynedcsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmynedcsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-diagonal-two-solid" {...props}></Icon>
