<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx58g5b5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zx58g5b5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:car-door-fill" {...props}></Icon>
