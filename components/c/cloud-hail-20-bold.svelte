<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dve4gcewv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dve4gcewv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-hail-20-bold" {...props}></Icon>
