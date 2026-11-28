<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyuvosbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyuvosbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-five-eighth-solid" {...props}></Icon>
