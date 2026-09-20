<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz-gipbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lz-gipbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:egg-line" {...props}></Icon>
