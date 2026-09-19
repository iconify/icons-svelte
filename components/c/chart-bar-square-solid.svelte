<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hov6vy65m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hov6vy65m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chart-bar-square-solid" {...props}></Icon>
