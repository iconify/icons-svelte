<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izgbbhbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izgbbhbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clipboard-plus-fill" {...props}></Icon>
