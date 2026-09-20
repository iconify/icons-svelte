<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfofu-cwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tfofu-cwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:announcement" {...props}></Icon>
