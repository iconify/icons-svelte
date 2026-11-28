<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cluy_9boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cluy_9boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:grip-vertical-solid" {...props}></Icon>
