<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shnmxq6pb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shnmxq6pb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:firebase" {...props}></Icon>
