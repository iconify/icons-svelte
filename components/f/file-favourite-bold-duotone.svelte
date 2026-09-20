<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j59i-d3bj.css';
import '../../css/w/wzmgbfbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j59i-d3bj"/><path class="wzmgbfbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-favourite-bold-duotone" {...props}></Icon>
