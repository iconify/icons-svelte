<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpdu8fdhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fpdu8fdhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bangladeshi-taka" {...props}></Icon>
