<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv4yr7owx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uv4yr7owx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:crystal-ball-filled" {...props}></Icon>
