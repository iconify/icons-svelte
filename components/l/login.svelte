<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubvq29b5w.css';
import '../../css/u/uoci6xb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ubvq29b5w"/><path class="uoci6xb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:login" {...props}></Icon>
