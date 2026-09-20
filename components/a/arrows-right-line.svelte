<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aig8m2tbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aig8m2tbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrows-right-line" {...props}></Icon>
