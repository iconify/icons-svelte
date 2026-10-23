<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st2ssyqcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st2ssyqcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:message-square-text" {...props}></Icon>
