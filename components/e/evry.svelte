<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fde_ztj2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fde_ztj2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:evry" {...props}></Icon>
