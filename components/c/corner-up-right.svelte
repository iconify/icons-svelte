<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ootsl4bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ootsl4bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:corner-up-right" {...props}></Icon>
