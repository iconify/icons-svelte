<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uujxc3myq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uujxc3myq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:hot-air-balloon-remix" {...props}></Icon>
