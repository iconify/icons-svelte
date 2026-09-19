<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzca4zbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzca4zbth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-right-2-light" {...props}></Icon>
