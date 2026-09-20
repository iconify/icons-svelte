<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcoz_bfrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hcoz_bfrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:airconditioner" {...props}></Icon>
