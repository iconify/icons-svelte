<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn3c1ccis.css';
import '../../css/c/c5ym2eb1u.css';
import '../../css/k/kfc99jb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vn3c1ccis"/><circle class="c5ym2eb1u"/><path class="kfc99jb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-sap-on-power" {...props}></Icon>
