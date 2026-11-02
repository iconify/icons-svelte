<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzhbvibbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzhbvibbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:minus-square-line" {...props}></Icon>
