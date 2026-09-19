<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crmd8sbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crmd8sbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:add-to-queue" {...props}></Icon>
