<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th1k_ebsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="th1k_ebsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:gradle" {...props}></Icon>
