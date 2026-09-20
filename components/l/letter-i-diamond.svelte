<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_q4f_bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_q4f_bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-i-diamond" {...props}></Icon>
