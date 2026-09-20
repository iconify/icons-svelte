<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdg7s_bla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="tdg7s_bla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:format-align-bottom" {...props}></Icon>
