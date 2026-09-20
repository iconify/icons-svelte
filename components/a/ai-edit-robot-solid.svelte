<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysn8ry8zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ysn8ry8zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:ai-edit-robot-solid" {...props}></Icon>
