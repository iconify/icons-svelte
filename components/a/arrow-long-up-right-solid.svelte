<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvq1r7byr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvq1r7byr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-long-up-right-solid" {...props}></Icon>
