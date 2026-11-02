<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bupor9x0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bupor9x0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heading-2-fill" {...props}></Icon>
