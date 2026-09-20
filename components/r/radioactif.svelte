<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw4f8xb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="iw4f8xb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:radioactif" {...props}></Icon>
