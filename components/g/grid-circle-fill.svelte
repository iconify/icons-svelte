<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks2y7_bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ks2y7_bis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:grid-circle-fill" {...props}></Icon>
