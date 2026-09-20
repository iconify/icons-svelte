<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bly2_8yev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bly2_8yev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hand-coin-line" {...props}></Icon>
