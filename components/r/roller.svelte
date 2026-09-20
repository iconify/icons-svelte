<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1zlls10b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="z1zlls10b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:roller" {...props}></Icon>
