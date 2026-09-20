<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsk3tsbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="dsk3tsbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:ring" {...props}></Icon>
