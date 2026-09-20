<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgz_ywmly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="kgz_ywmly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:barcode" {...props}></Icon>
