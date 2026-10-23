<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnlo_9ctj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnlo_9ctj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cigarette" {...props}></Icon>
