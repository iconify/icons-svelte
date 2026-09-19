<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm_k9ga6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zm_k9ga6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:pgt" {...props}></Icon>
