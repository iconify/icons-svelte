<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exguqts2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="exguqts2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:ribbon" {...props}></Icon>
