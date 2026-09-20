<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px824wbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="px824wbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-up-right-waves-solid" {...props}></Icon>
