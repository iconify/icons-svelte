<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7q2ahz_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="m7q2ahz_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:indent" {...props}></Icon>
