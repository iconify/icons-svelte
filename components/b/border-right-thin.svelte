<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk63w7-dx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jk63w7-dx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:border-right-thin" {...props}></Icon>
