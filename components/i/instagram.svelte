<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjc6tp_vo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjc6tp_vo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:instagram" {...props}></Icon>
