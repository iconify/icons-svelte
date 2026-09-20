<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lck50fbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="lck50fbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:cloud-up" {...props}></Icon>
