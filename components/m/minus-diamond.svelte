<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg7r_suvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sg7r_suvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:minus-diamond" {...props}></Icon>
