<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_svioi-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="g_svioi-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:dot" {...props}></Icon>
