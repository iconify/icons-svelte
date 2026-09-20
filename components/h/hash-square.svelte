<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc7-p9bkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc7-p9bkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:hash-square" {...props}></Icon>
