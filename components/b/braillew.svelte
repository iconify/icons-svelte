<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjnv0c0fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="hjnv0c0fo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:braillew" {...props}></Icon>
