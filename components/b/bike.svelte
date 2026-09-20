<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3fj27jqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3fj27jqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:bike" {...props}></Icon>
