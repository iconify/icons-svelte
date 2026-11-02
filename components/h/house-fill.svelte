<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtaosvumk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtaosvumk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:house-fill" {...props}></Icon>
