<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnxf5iqlo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":469,"height":512};
const content = `<path class="fnxf5iqlo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:ansible-alt" {...props}></Icon>
