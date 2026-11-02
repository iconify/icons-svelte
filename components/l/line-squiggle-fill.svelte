<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k74wagwxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k74wagwxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:line-squiggle-fill" {...props}></Icon>
