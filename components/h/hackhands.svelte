<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za0_gwbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="za0_gwbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:hackhands" {...props}></Icon>
