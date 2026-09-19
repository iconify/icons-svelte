<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sptpt9b4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sptpt9b4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloud-haze2" {...props}></Icon>
