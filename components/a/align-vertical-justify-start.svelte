<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmi25bcfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmi25bcfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:align-vertical-justify-start" {...props}></Icon>
