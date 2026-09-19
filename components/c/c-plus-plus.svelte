<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8-p5lbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8-p5lbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:c-plus-plus" {...props}></Icon>
