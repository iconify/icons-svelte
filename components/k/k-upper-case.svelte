<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csg_4pb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":491,"height":735};
const content = `<path class="csg_4pb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:k-upper-case" {...props}></Icon>
