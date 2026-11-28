<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf33qeb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wf33qeb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:minimize-solid" {...props}></Icon>
