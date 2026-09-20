<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1en0g5bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1en0g5bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-forward-square-30-fill" {...props}></Icon>
