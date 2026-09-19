<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggts764pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggts764pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:restaurant" {...props}></Icon>
