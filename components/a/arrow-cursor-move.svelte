<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv73z5bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lv73z5bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:arrow-cursor-move" {...props}></Icon>
