<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbjuqgbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbjuqgbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:g2" {...props}></Icon>
