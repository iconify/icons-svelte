<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c51wj6ovw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="c51wj6ovw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:flood" {...props}></Icon>
