<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvntz0b2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="cvntz0b2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-bottom-left" {...props}></Icon>
