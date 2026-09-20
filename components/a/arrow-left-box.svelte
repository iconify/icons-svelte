<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_mwxib-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="z_mwxib-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-left-box" {...props}></Icon>
