<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-ezt7pyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-ezt7pyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:citrus-solid" {...props}></Icon>
