<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh06vnbum.css';
import '../../css/h/htce_l0gk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eh06vnbum"/><path class="htce_l0gk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:catalog" {...props}></Icon>
