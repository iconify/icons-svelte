<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqe_-bb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eqe_-bb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nasm" {...props}></Icon>
