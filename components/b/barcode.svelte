<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9dlsrbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="p9dlsrbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:barcode" {...props}></Icon>
