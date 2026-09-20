<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcie1_bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="hcie1_bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:format-text" {...props}></Icon>
