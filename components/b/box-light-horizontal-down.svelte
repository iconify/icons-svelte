<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytf2gtbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ytf2gtbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-horizontal-down" {...props}></Icon>
