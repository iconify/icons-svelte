<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_6x5wbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_6x5wbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-down-right-duotone-round" {...props}></Icon>
