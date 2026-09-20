<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq3wg0bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xq3wg0bvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:module-puzzle-2-solid" {...props}></Icon>
