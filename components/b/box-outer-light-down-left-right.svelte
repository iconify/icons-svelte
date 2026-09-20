<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcyll2bph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="pcyll2bph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-down-left-right" {...props}></Icon>
