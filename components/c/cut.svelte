<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek_n8cbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ek_n8cbpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:cut" {...props}></Icon>
